<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sk7ocbcqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sk7ocbcqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:crown-minus" /></template>

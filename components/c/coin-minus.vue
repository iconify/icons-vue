<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qvfk_ofog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qvfk_ofog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:coin-minus" /></template>

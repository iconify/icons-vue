<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ivlssacxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ivlssacxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:folder-minus" /></template>

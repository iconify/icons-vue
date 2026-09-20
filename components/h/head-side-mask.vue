<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pil_nmbqz.css';
import '../../css/y/ydj8k-bvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pil_nmbqz"/><path class="ydj8k-bvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:head-side-mask" /></template>

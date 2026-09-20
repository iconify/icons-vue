<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e750u5bvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e750u5bvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:line-spacing" /></template>

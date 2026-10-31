<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j8z640bsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j8z640bsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hexagon-bulk-round" /></template>

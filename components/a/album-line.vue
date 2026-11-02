<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qem2vs-wc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qem2vs-wc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:album-line" /></template>

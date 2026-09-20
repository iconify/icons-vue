<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ubzqx4l4f.css';
import '../../css/u/uhypokb_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ubzqx4l4f"/><path class="uhypokb_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chart-vertical-2-line" /></template>

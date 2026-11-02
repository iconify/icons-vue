<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hng45_bfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hng45_bfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:captions-off-line" /></template>

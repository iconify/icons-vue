<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1-qxeb8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x1-qxeb8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:large-arrow-up-line" /></template>

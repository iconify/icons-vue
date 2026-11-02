<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-e5hmj2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m-e5hmj2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:combine-2-line" /></template>

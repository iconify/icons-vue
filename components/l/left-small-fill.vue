<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i0pd4igad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i0pd4igad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:left-small-fill" /></template>

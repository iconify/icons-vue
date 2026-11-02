<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ucae7xdov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ucae7xdov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:align-vertical-distribute-start-line" /></template>

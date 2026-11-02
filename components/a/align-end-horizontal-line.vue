<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n70tk6bly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n70tk6bly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:align-end-horizontal-line" /></template>

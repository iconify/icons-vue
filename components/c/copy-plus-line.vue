<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ze3wtqlis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ze3wtqlis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:copy-plus-line" /></template>

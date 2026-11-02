<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cc458yufi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cc458yufi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:father-christmas-line" /></template>

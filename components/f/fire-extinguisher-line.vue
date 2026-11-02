<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gvb0yvbbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gvb0yvbbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:fire-extinguisher-line" /></template>

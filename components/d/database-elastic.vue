<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fm_aatb_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fm_aatb_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:database-elastic" /></template>

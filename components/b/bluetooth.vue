<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pcixz7jrf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1344,"height":1792};
const content = `<path class="pcixz7jrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:bluetooth" /></template>

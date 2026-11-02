<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gqayykb8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gqayykb8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:circle-chevron-left-fill" /></template>

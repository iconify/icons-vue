<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7-9x2bvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s7-9x2bvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:group-3-fill" /></template>

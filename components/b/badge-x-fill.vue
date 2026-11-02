<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x42n11b_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x42n11b_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:badge-x-fill" /></template>

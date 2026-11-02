<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1wj4u1yf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x1wj4u1yf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:gallery-horizontal-line" /></template>

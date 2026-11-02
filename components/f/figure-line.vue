<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpy135b_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lpy135b_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:figure-line" /></template>

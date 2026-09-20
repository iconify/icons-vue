<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/snniw392r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="snniw392r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bluetooth-line" /></template>

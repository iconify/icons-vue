<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bd3epf6yf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bd3epf6yf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:ie-line" /></template>

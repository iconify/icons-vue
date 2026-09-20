<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n188czbny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n188czbny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:contract-line" /></template>

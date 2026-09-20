<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h1dz7wbah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h1dz7wbah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:4k-line" /></template>

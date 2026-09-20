<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lc7r4x4eu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lc7r4x4eu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:book-line" /></template>

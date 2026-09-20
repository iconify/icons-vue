<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5kgqwblt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e5kgqwblt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:hd-line" /></template>

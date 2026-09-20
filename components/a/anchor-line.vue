<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fz4uxmb5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fz4uxmb5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:anchor-line" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-xpgstal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n-xpgstal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:brain-line" /></template>

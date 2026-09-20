<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fc3i_-79p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fc3i_-79p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:at-line" /></template>

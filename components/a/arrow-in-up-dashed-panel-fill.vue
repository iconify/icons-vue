<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wdd7vy8ix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wdd7vy8ix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-in-up-dashed-panel-fill" /></template>

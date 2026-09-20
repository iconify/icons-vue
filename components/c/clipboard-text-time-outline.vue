<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/reuqw7bwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="reuqw7bwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:clipboard-text-time-outline" /></template>

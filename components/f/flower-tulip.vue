<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l5t6t7bhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l5t6t7bhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:flower-tulip" /></template>

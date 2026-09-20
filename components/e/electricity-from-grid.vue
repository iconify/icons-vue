<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhf8m9a1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yhf8m9a1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:electricity-from-grid" /></template>

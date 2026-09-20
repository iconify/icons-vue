<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sh3x2sb7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sh3x2sb7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:film-plus-outline" /></template>

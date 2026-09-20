<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jxg82f72d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jxg82f72d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:locations-outline" /></template>

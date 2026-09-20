<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jbt99e3-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jbt99e3-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bow-arrow" /></template>

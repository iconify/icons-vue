<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/avo0fx4sb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="avo0fx4sb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:baby-bottle" /></template>

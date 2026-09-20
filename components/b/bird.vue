<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sx4lt75ew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sx4lt75ew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bird" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/avq65hbna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="avq65hbna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:hydraulic-oil-level" /></template>

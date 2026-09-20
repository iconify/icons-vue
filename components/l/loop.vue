<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi5cw-bdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bi5cw-bdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:loop" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mw8p30bge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mw8p30bge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:corner-up-right-double-fill" /></template>

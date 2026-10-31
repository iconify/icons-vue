<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hik5r3n6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hik5r3n6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:crown-fill-round" /></template>

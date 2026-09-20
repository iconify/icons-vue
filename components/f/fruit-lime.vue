<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/unpu3551h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="unpu3551h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:fruit-lime" /></template>

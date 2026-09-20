<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m--fc-7uw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m--fc-7uw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:language-markdown" /></template>

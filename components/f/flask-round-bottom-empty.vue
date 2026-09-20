<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6ra722lh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f6ra722lh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:flask-round-bottom-empty" /></template>

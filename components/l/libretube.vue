<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_-9k8bbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d_-9k8bbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:libretube" /></template>

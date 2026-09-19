<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yt7esm00f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yt7esm00f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:label" /></template>

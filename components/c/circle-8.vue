<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xfrcz0m3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xfrcz0m3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:circle-8" /></template>

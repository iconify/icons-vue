<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ur_hjldrr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ur_hjldrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:circle" /></template>

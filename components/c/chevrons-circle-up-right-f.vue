<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q95gpxbql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="q95gpxbql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:chevrons-circle-up-right-f" /></template>

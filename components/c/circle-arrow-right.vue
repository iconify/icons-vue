<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w0z9cybyf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w0z9cybyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-arrow-right" /></template>

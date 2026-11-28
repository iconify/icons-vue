<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7jhlr5nh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u7jhlr5nh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:boxes-check" /></template>

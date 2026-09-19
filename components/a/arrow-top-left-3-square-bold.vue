<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yi03icced.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yi03icced"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-top-left-3-square-bold" /></template>

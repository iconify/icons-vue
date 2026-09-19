<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e3txsfb9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e3txsfb9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-top-left-1" /></template>

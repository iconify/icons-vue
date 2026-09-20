<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cncj86rwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cncj86rwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:book-education-outline" /></template>

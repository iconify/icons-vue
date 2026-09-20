<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nox49tb7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nox49tb7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:calendar-star-four-points" /></template>

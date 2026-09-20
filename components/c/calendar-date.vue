<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f13y2qh5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f13y2qh5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:calendar-date" /></template>

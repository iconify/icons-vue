<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/au4xtbchb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="au4xtbchb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:carousel-v-filled" /></template>

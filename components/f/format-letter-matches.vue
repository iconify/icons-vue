<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cncna5pxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cncna5pxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:format-letter-matches" /></template>

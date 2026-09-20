<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r1h8vubxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r1h8vubxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cards-variant" /></template>

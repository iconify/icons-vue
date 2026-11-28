<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uj9x2t-hb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uj9x2t-hb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:apple-heart" /></template>

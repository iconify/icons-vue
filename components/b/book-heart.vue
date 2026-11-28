<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rohs4-bkb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rohs4-bkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:book-heart" /></template>

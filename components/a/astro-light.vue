<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1-5inbbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":85,"height":107};
const content = `<path class="w1-5inbbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:astro-light" /></template>

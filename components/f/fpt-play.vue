<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/evbg5bcoz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":279.62,"height":279.9};
const content = `<path class="evbg5bcoz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:fpt-play" /></template>

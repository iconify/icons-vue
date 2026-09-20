<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c525gmbvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":554,"height":137};
const content = `<path class="c525gmbvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:espn" /></template>

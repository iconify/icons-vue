<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pys7aibts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pys7aibts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:creative-commons-remix" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hxoeczbkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hxoeczbkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:crowbar-48-bold" /></template>

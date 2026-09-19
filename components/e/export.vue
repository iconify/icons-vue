<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ru_up_-lr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ru_up_-lr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:export" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tb1dfb9ww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tb1dfb9ww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:clothes-sweater" /></template>

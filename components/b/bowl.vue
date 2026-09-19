<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-cyptbab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u-cyptbab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:bowl" /></template>

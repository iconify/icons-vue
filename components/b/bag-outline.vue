<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tbqohkbac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tbqohkbac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:bag-outline" /></template>

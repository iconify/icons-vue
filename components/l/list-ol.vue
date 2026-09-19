<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wntykgjde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wntykgjde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:list-ol" /></template>

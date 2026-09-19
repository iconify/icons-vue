<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v54s_nbpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="v54s_nbpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:frog" /></template>

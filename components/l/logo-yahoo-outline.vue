<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvk1xwstj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zvk1xwstj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:logo-yahoo-outline" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rs95uib-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rs95uib-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:logo-wikinews" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdyaibcnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="mdyaibcnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:health-medical-ribbon-2-ribbon-medical-cancer-health-beauty-symbol" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tr-eedcjf.css';
import '../../css/r/rqb2ygbhr.css';
import '../../css/z/zb4cfkbur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tr-eedcjf"/><path class="rqb2ygbhr"/><path class="zb4cfkbur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:district-heating-48-bold" /></template>

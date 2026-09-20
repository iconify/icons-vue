<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nfqdlls5m.css';
import '../../css/u/uhxg3ozyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":250,"height":250};
const content = `<path class="nfqdlls5m"/><path class="uhxg3ozyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:charles-schwab" /></template>

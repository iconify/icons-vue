<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uhzw_ibjg.css';
import '../../css/f/fudbgdb1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":330};
const content = `<path class="uhzw_ibjg"/><path class="fudbgdb1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:hono" /></template>

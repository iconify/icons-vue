<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bb76z_6xl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bb76z_6xl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:ballotboldscriptx" /></template>

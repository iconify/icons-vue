<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmy7jtbal.css';
import '../../css/u/u01dg9zki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mmy7jtbal"/><path class="u01dg9zki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:chatgpt" /></template>

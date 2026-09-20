<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wb86ohshj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wb86ohshj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:half-star-ltr" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lde70vbjm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lde70vbjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:half-star-rtl" /></template>

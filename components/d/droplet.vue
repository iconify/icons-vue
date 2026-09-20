<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j0day-b1r.css';
import '../../css/r/rzjiq6ajn.css';
import '../../css/j/jce5cjb-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="j0day-b1r"/><path class="rzjiq6ajn"/><path class="jce5cjb-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:droplet" /></template>

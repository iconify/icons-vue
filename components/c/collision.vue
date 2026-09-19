<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwss-ebkl.css';
import '../../css/b/bd5wmoffp.css';
import '../../css/q/qdq3nabuw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rwss-ebkl"/><path class="bd5wmoffp"/><path class="qdq3nabuw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:collision" /></template>

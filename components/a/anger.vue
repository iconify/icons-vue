<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dd_-6ac5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dd_-6ac5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:anger" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ez9qunc8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ez9qunc8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:align-top-two" /></template>

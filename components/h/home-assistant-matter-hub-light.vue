<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufun8cc7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ufun8cc7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:home-assistant-matter-hub-light" /></template>

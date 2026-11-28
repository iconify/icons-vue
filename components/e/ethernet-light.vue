<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dny39646t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="dny39646t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:ethernet-light" /></template>

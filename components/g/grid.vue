<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a7hn-9ncr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="a7hn-9ncr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:grid" /></template>

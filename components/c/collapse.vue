<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xek9-rddj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":42};
const content = `<path class="xek9-rddj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="topcoat:collapse" /></template>

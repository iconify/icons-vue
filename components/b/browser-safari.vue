<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8nrbqb1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x8nrbqb1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:browser-safari" /></template>

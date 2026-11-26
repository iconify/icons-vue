<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nixhzr23g.css';
import '../../css/l/lpeb5vbby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<g transform="matrix(2.4 0 0 2.4 14.897 -33.423)"><ellipse class="nixhzr23g"/><ellipse class="lpeb5vbby"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="xero-emoji:hole" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q1365bb5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q1365bb5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:canadian-maple-leaf" /></template>

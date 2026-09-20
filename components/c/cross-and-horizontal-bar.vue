<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lx1giabeb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lx1giabeb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:cross-and-horizontal-bar" /></template>

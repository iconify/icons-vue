<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rrjp8zb7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rrjp8zb7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:circle-close-outline" /></template>

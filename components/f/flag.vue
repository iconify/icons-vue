<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rmetvov-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rmetvov-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:flag" /></template>

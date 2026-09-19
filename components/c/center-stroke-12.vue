<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ds-s1ulgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ds-s1ulgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:center-stroke-12" /></template>

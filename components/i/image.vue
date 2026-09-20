<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oi8rvybjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oi8rvybjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:image" /></template>

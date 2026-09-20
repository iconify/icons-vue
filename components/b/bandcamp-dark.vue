<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnm-5gseg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rnm-5gseg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:bandcamp-dark" /></template>

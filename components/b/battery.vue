<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-cl05b2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":216,"height":432};
const content = `<path class="u-cl05b2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:battery" /></template>

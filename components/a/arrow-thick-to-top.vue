<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/inlhb1gzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="inlhb1gzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:arrow-thick-to-top" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/blbpfrbam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="blbpfrbam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:hexagon-vertical-bars-database" /></template>

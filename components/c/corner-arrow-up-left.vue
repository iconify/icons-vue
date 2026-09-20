<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a3v2b3wcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a3v2b3wcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:corner-arrow-up-left" /></template>

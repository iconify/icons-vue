<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-uwexb4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u-uwexb4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hhf-technology-light" /></template>

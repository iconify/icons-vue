<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s1gjrv-xu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="s1gjrv-xu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:link-stroke-12" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d91b1m4xa.css';
import '../../css/d/deymd5jrm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="d91b1m4xa"/><path class="deymd5jrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:external-link-16" /></template>

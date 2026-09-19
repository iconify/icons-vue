<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/delp4wn8f.css';
import '../../css/n/n273d0b2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="delp4wn8f"/><path class="n273d0b2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:document-configuration" /></template>

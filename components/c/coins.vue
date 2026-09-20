<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzo-h1bfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dzo-h1bfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:coins" /></template>

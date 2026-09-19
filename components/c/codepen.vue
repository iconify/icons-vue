<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bchvfg87t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bchvfg87t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:codepen" /></template>

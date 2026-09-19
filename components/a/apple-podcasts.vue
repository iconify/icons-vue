<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gklcnactc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gklcnactc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:apple-podcasts" /></template>

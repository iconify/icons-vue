<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ucpq15tnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ucpq15tnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:chevron-expand-sharp" /></template>

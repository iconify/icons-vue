<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kj1oo60oz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kj1oo60oz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:element-light" /></template>

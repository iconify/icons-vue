<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/src-bncvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="src-bncvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kubero" /></template>

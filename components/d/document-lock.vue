<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/llzqa-0gd.css';
import '../../css/w/wkau1rbrb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="llzqa-0gd"/><path class="wkau1rbrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:document-lock" /></template>

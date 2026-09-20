<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cfv2_eccz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cfv2_eccz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ergo" /></template>

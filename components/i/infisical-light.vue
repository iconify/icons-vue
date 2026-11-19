<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zujux2bdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zujux2bdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:infisical-light" /></template>

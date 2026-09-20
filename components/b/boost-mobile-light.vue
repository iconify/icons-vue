<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aj8dscbxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="aj8dscbxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:boost-mobile-light" /></template>

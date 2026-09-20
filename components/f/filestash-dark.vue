<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cf66cyj2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cf66cyj2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:filestash-dark" /></template>

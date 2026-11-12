<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zjafvc-tm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zjafvc-tm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hydrus-web-dark" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e60mj5bkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e60mj5bkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:file-explorer-light" /></template>

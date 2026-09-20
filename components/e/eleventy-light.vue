<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eo8k09bah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="eo8k09bah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:eleventy-light" /></template>

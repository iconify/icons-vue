<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/krbfg6bkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="krbfg6bkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:brotli" /></template>

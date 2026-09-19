<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kxlicvb1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kxlicvb1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:code-download" /></template>

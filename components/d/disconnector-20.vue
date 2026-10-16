<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cds5php0e.css';
import '../../css/w/w2rqhou5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cds5php0e"/><path class="w2rqhou5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:disconnector-20" /></template>

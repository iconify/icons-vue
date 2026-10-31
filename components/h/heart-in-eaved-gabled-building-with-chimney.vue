<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bq-rkobcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="bq-rkobcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:heart-in-eaved-gabled-building-with-chimney" /></template>

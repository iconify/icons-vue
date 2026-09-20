<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kgz_ywmly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="kgz_ywmly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:barcode" /></template>

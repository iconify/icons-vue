<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/poga9shhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="poga9shhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-global-storage-architecture" /></template>

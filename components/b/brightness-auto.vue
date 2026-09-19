<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zk8kwsb0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":488,"height":496};
const content = `<path class="zk8kwsb0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:brightness-auto" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p0064doyk.css';
import '../../css/m/m8qdx0f9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p0064doyk"/><path class="m8qdx0f9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:buggregator-light" /></template>

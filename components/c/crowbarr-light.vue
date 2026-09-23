<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lt5h2-4uq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lt5h2-4uq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:crowbarr-light" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djxmmft-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="djxmmft-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:collection-add" /></template>

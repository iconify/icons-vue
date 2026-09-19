<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/puuzwgb1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":384};
const content = `<path class="puuzwgb1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:folder-special" /></template>

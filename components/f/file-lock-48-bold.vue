<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/frd-8-btx.css';
import '../../css/p/p9big2yaj.css';
import '../../css/u/uir1vq-bm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="frd-8-btx"/><path class="p9big2yaj"/><path class="uir1vq-bm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:file-lock-48-bold" /></template>

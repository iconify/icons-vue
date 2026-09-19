<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/btq232bkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="btq232bkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:dot-net" /></template>

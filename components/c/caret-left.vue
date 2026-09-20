<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/brc8u4q-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="brc8u4q-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:caret-left" /></template>

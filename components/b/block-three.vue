<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xvor92b2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xvor92b2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:block-three" /></template>

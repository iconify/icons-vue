<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ykjovtd5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ykjovtd5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:block-two" /></template>

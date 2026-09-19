<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v26rpkb4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v26rpkb4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:backward-fast" /></template>

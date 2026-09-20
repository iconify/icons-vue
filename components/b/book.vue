<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_qsx6bnj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z_qsx6bnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:book" /></template>

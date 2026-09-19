<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ck65vcc4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":416,"height":512};
const content = `<path class="ck65vcc4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:fauna" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lhevx-b8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="lhevx-b8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-light-vertical-circle" /></template>

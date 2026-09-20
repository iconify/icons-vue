<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lzdioebup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="lzdioebup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-light-double-up-left" /></template>

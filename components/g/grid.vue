<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m36qdbdcv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="m36qdbdcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:grid" /></template>

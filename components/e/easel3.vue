<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dqv60rbne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dqv60rbne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:easel3" /></template>

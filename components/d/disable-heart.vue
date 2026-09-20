<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9e90ybcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z9e90ybcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:disable-heart" /></template>

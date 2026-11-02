<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zc_4xoalh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zc_4xoalh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:corners-pointing-in-16-solid" /></template>

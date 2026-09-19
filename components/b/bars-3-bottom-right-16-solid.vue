<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ztf73cbph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ztf73cbph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:bars-3-bottom-right-16-solid" /></template>

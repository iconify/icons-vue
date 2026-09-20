<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pnzp6-gsx.css';
import '../../css/w/wl3st4cag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="pnzp6-gsx"/><path clip-rule="evenodd" class="wl3st4cag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:chevron-double-up-16" /></template>

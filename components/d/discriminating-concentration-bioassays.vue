<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pxdnbvbmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="pxdnbvbmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:discriminating-concentration-bioassays" /></template>

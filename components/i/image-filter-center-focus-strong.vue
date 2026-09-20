<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xfxy0ht-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xfxy0ht-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:image-filter-center-focus-strong" /></template>

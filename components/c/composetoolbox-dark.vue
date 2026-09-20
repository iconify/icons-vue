<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nzwc3f7as.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nzwc3f7as"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:composetoolbox-dark" /></template>

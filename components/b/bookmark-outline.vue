<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/erpo1w27n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="erpo1w27n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:bookmark-outline" /></template>

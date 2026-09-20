<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3cf4bbin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s3cf4bbin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:curves-levels-graph-solid" /></template>

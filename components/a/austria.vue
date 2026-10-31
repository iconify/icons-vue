<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jfb26sb-e.css';
import '../../css/d/d1x_6zbkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="jfb26sb-e"/><path class="d1x_6zbkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:austria" /></template>

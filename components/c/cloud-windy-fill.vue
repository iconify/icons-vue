<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xu4w_7b6f.css';
import '../../css/e/eov2hibfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xu4w_7b6f"/><path class="eov2hibfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cloud-windy-fill" /></template>

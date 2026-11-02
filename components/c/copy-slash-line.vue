<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ztdlx5baf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ztdlx5baf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:copy-slash-line" /></template>

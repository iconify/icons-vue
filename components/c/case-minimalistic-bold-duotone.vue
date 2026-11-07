<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydbsjp0mn.css';
import '../../css/u/uv9075bbf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ydbsjp0mn"/><path class="uv9075bbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:case-minimalistic-bold-duotone" /></template>

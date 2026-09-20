<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xq3c38dxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xq3c38dxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:gowalla-logo-3-block" /></template>

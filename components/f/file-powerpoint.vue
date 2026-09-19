<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xr14weswy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xr14weswy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:file-powerpoint" /></template>

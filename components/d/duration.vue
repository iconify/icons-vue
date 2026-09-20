<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ybc_wgbhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ybc_wgbhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:duration" /></template>

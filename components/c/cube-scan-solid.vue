<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nsgvmwn9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nsgvmwn9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:cube-scan-solid" /></template>

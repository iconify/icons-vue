<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qv2o3kbcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qv2o3kbcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:adobe-animate-logo-solid" /></template>

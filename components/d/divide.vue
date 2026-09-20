<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eo02nxhcm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eo02nxhcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:divide" /></template>

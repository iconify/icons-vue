<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxnxkm_gj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qxnxkm_gj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:dam-3-filled" /></template>

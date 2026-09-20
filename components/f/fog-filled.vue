<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qeb6jzb_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qeb6jzb_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:fog-filled" /></template>

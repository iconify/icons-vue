<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dts291b_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dts291b_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:ghost-filled" /></template>

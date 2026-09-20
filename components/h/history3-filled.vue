<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o244-4_zh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o244-4_zh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:history3-filled" /></template>

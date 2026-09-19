<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qeq6kv7wx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qeq6kv7wx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxl-facebook-square" /></template>

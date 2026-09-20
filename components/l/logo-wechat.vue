<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqm469b_j.css';
import '../../css/m/mjpn8j_wb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uqm469b_j"/><path class="mjpn8j_wb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:logo-wechat" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9awjfzyj.css';
import '../../css/f/f7niv6bbj.css';
import '../../css/f/figjuehvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l9awjfzyj"/><path class="f7niv6bbj"/><path class="figjuehvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:lidar-48-bold" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/os_e7fbgt.css';
import '../../css/b/b8g_udb9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="os_e7fbgt"/><path class="b8g_udb9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:chip" /></template>

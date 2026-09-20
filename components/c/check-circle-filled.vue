<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zv7mem_ke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zv7mem_ke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:check-circle-filled" /></template>

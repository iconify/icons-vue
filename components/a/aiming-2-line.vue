<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvnh_wvmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yvnh_wvmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:aiming-2-line" /></template>

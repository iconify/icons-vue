<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qem7g_bfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qem7g_bfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:calender" /></template>

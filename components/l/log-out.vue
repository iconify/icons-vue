<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5-h-rzii.css';
import '../../css/d/d01u25bof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s5-h-rzii"/><path class="d01u25bof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:log-out" /></template>

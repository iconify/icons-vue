<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zr_1r9b1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zr_1r9b1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:alarm-clock-off" /></template>

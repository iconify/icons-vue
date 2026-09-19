<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_vsx4b1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c_vsx4b1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-calendar-alt" /></template>

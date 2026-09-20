<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ikpp05bgn.css';
import '../../css/t/ta9uhpgzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ikpp05bgn"/><path class="ta9uhpgzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:linkedin" /></template>

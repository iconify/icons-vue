<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6u7tw-2d.css';
import '../../css/b/by38gccqr.css';
import '../../css/y/y_-z-8r0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b j6u7tw-2d"/><path class="b by38gccqr"/><path class="b y_-z-8r0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:camera-alt" /></template>

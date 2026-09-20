<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ys2xnwm9y.css';
import '../../css/c/cc8xe5byi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ys2xnwm9y"/><path class="cc8xe5byi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bear-line" /></template>

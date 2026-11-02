<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn4gjdhja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xn4gjdhja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:image-off-line" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jk-wzp8cc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jk-wzp8cc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:homepod-mini-line" /></template>

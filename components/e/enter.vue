<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l876m5b_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l876m5b_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:enter" /></template>

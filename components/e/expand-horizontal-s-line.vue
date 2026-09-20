<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yy_6qlgcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yy_6qlgcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:expand-horizontal-s-line" /></template>

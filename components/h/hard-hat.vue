<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxk1z3lyq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zxk1z3lyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:hard-hat" /></template>

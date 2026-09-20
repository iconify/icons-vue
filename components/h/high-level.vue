<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzkaz2bsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dzkaz2bsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:high-level" /></template>

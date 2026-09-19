<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7b6xyuqs.css';
import '../../css/e/ez6lwcbzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w7b6xyuqs"/><path class="ez6lwcbzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-school" /></template>

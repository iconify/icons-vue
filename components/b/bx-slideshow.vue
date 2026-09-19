<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pglqq_f1q.css';
import '../../css/t/trfu-vbwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pglqq_f1q"/><path class="trfu-vbwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-slideshow" /></template>

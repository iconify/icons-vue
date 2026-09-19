<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qyoj2sb5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qyoj2sb5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-quote-alt-left" /></template>

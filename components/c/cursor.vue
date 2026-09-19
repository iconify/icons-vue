<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xqp-onbdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xqp-onbdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:cursor" /></template>

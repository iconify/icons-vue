<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvcg5__wh.css';
import '../../css/c/ch6_fcbjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yvcg5__wh"/><path class="ch6_fcbjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-message-add" /></template>

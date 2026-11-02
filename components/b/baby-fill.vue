<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zqp7-xwht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zqp7-xwht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:baby-fill" /></template>

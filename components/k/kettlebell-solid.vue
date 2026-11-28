<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zk-6q41wh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zk-6q41wh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:kettlebell-solid" /></template>

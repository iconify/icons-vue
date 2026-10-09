<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rpx9c7b2s.css';
import '../../css/a/a_0kltb3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rpx9c7b2s"/><path class="a_0kltb3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:house-leaf-20" /></template>

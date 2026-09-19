<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwaa64zik.css';
import '../../css/y/yv_brepse.css';
import '../../css/r/rykla9wen.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="uwaa64zik"/><path class="yv_brepse"/><path class="rykla9wen"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:left-circle-twotone" /></template>

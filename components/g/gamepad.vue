<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qidryvbbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1920,"height":1280};
const content = `<path class="qidryvbbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:gamepad" /></template>

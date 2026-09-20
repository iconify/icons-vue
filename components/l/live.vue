<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvtnscbtx.css';
import '../../css/y/yzo5plbsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vvtnscbtx"/><circle class="yzo5plbsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:live" /></template>

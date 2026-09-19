<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wqh1l2nbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="wqh1l2nbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:java-script-outlined" /></template>

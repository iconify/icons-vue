<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vc76v9bka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="vc76v9bka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:caret-up" /></template>

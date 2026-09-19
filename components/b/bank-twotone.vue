<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eqmh9p0fn.css';
import '../../css/v/vv7d6sb3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="eqmh9p0fn"/><path class="vv7d6sb3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:bank-twotone" /></template>

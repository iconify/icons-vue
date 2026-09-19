<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zv3a_cc7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="zv3a_cc7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:caret-down-8" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lkjpt4ruz.css';
import '../../css/x/xoqcm6b1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="lkjpt4ruz"/><path class="xoqcm6b1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:layer-edit" /></template>

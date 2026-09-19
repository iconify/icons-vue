<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmdgq1b2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="zmdgq1b2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:blogger-b" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q1wxr2brf.css';
import '../../css/x/x6-25tkfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="q1wxr2brf"/><path class="x6-25tkfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:gold-twotone" /></template>

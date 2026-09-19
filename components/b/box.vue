<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xmhxj5bon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":740,"height":750};
const content = `<path class="xmhxj5bon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:box" /></template>

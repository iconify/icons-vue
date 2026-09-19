<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nsftthb-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="nsftthb-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:jar-wheat" /></template>

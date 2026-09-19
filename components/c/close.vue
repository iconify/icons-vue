<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bgj5nhvcz.css';
import '../../css/m/mjyk0m7ab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":16};
const content = `<path class="bgj5nhvcz"/><path class="mjyk0m7ab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:close" /></template>

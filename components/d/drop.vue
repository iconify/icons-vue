<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qlth1jb1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="qlth1jb1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:drop" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xvc65utye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="xvc65utye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:cold-drink" /></template>

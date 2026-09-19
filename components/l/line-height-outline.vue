<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-z42tc9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="c-z42tc9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:line-height-outline" /></template>

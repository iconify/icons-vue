<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vtat75bif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="vtat75bif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:caret-down-fill" /></template>

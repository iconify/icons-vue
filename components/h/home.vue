<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j72nmtz-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="j72nmtz-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:home" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ok0x02bci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ok0x02bci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:coffee" /></template>

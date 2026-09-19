<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z5asd1mya.css';
import '../../css/w/w893w9fet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="z5asd1mya"/><path class="w893w9fet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:cloud-download-outlined" /></template>

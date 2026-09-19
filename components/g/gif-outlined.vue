<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fkba3m0qr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="fkba3m0qr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:gif-outlined" /></template>

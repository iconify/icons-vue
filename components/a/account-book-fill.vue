<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djrt-nrht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="djrt-nrht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:account-book-fill" /></template>

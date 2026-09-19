<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kno4j37zf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="kno4j37zf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:euro-circle-fill" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kxqyng7lr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="kxqyng7lr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:clear-outlined" /></template>

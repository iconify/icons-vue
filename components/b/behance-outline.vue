<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/th2y76b6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="th2y76b6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:behance-outline" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2u7zvnem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="s2u7zvnem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:desktop-outlined" /></template>

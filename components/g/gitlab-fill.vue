<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvjq4ab0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="vvjq4ab0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:gitlab-fill" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dh21mpa7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="dh21mpa7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:border-verticle" /></template>

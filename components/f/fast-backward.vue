<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ce2gzmb0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ce2gzmb0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:fast-backward" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7mwa9bbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="z7mwa9bbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:code-sandbox-square-fill" /></template>

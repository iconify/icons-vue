<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_np747ww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="e_np747ww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:code-sandbox-circle-filled" /></template>

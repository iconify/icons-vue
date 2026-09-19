<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a6ih8ibvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="a6ih8ibvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:edit-fill" /></template>

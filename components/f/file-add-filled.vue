<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u8t1wibbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="u8t1wibbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:file-add-filled" /></template>

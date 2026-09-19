<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j3jb4gb8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="j3jb4gb8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:eleven-labs-filled" /></template>

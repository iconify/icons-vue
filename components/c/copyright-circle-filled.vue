<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_v3zxy6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="x_v3zxy6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:copyright-circle-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vq-4co-2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="vq-4co-2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:amazon" /></template>

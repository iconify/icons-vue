<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ftij1dlzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ftij1dlzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:claude-filled" /></template>

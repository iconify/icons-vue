<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9atepzeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="v9atepzeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:contacts-outlined" /></template>

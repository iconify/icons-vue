<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zjcm6d98u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="zjcm6d98u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:discord-outlined" /></template>

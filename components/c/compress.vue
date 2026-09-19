<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aty5o6b6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="aty5o6b6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:compress" /></template>

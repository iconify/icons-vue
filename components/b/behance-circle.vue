<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wx441kbdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="wx441kbdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:behance-circle" /></template>

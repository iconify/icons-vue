<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hui4rqb0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="hui4rqb0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:car-outlined" /></template>

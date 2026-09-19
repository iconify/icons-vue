<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/leg-t8bwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="leg-t8bwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:mail-outlined" /></template>

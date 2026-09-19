<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/prq31rbnp.css';
import '../../css/u/u-0d80bqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="prq31rbnp"/><path class="u-0d80bqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:fund-projection-screen-outlined" /></template>

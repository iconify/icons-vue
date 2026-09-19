<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dky0zvbmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="dky0zvbmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:box-plot-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjx5ey33j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qjx5ey33j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:book-store" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lexve4bbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="lexve4bbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:board-train-bullet" /></template>

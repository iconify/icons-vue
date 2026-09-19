<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xzzb4x5sj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="xzzb4x5sj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:calendar" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n520rw5zl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="n520rw5zl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:7" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bn36qn67e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="bn36qn67e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:battery-4" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gb2ic2ncu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":832};
const content = `<path class="gb2ic2ncu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:copyapp" /></template>

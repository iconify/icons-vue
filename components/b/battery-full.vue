<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zopwkq5cj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="zopwkq5cj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:battery-full" /></template>

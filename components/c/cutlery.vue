<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zads2pb3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="zads2pb3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:cutlery" /></template>

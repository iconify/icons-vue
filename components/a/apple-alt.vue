<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zck3w-1kz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zck3w-1kz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:apple-alt" /></template>

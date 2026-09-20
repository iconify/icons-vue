<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zhd9nx_yo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zhd9nx_yo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:indent-solid" /></template>

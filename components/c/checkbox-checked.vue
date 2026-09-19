<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hxv8z0l9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hxv8z0l9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:checkbox-checked" /></template>

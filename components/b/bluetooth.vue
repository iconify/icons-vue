<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udl_u4bup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="udl_u4bup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:bluetooth" /></template>

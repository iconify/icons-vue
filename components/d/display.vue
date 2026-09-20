<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ysi0uubkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="ysi0uubkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:display" /></template>

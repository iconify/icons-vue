<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qkc4zgroo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qkc4zgroo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:arm" /></template>

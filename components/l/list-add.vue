<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xjqawm_sp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="xjqawm_sp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:list-add" /></template>

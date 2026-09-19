<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_jz6jb-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y_jz6jb-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:leg-outline" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxk146b4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="zxk146b4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:cardiology" /></template>

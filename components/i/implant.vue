<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ytck23rpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ytck23rpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:implant" /></template>

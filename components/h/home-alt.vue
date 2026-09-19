<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0mko4zde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z0mko4zde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:home-alt" /></template>

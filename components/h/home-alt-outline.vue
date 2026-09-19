<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ye931s0lu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ye931s0lu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:home-alt-outline" /></template>

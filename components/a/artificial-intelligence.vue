<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt33t8g3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dt33t8g3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:artificial-intelligence" /></template>

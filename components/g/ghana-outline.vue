<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ycr3-ac1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ycr3-ac1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:ghana-outline" /></template>

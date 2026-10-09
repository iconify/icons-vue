<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mo1yxebdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mo1yxebdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:caret-left-48" /></template>

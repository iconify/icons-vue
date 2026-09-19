<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iyjz5_xhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="iyjz5_xhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:cancel" /></template>

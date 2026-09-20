<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yw19jlmwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="yw19jlmwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:2f-swipe-down" /></template>

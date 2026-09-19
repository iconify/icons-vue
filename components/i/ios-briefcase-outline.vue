<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_f6ecczd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m_f6ecczd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-briefcase-outline" /></template>

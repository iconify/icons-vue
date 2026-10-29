<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wvphuy7cx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wvphuy7cx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:jalebi-solid" /></template>

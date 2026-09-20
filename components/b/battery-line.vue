<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/npak40b9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="npak40b9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:battery-line" /></template>

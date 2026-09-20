<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xfb3x1bkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xfb3x1bkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:database-sync" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/efs_2kbto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="efs_2kbto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:clouds" /></template>

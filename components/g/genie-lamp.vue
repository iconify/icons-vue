<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/af696vz5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="af696vz5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:genie-lamp" /></template>

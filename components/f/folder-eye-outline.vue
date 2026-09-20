<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wdedo1bdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wdedo1bdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:folder-eye-outline" /></template>

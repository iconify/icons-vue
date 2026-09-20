<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vowv2jbsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vowv2jbsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:arcgis" /></template>

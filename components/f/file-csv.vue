<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmzbb3bza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gmzbb3bza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-csv" /></template>

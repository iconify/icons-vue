<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ni45svb9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ni45svb9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:gps-not-fixed" /></template>

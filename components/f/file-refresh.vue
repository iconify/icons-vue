<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwmw_7gsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mwmw_7gsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-refresh" /></template>

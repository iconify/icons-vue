<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vl0rz-b0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vl0rz-b0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-eye-outline" /></template>

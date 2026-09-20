<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zy6vjcb_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zy6vjcb_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:download-outline" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1ip_wbdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u1ip_wbdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:blender-software" /></template>

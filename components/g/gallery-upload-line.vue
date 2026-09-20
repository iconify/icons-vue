<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmi3wdbpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mmi3wdbpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:gallery-upload-line" /></template>

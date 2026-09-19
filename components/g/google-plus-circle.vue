<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hrdd82b1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hrdd82b1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:google-plus-circle" /></template>

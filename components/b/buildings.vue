<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-hct6byl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-hct6byl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:buildings" /></template>

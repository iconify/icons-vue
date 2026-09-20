<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-5_mcc4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l-5_mcc4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:magic-edit" /></template>

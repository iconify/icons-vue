<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ia65cdbfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ia65cdbfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:diamond-stone" /></template>

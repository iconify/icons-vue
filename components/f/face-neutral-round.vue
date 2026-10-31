<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pn2xogvfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pn2xogvfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:face-neutral-round" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/agaqwoz2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="agaqwoz2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:document-layout-center" /></template>

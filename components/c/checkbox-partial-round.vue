<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/msi2722la.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="msi2722la"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:checkbox-partial-round" /></template>

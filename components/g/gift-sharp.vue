<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2496vbfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m2496vbfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:gift-sharp" /></template>

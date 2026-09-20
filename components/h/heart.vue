<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mnvd4kpgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mnvd4kpgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:heart" /></template>

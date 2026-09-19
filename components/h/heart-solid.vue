<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s741nbbew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s741nbbew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:heart-solid" /></template>

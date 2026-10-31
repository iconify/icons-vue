<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pwy2qg0za.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pwy2qg0za"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:eagle-fill-round" /></template>

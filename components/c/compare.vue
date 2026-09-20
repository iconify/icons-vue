<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rduz3kbha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rduz3kbha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:compare" /></template>

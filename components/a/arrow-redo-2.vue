<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/seli0bcod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="seli0bcod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:arrow-redo-2" /></template>

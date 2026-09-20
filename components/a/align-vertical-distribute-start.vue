<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/drp98crri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="drp98crri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:align-vertical-distribute-start" /></template>

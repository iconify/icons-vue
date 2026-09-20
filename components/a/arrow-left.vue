<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wdwbvabne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wdwbvabne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:arrow-left" /></template>

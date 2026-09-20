<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ih_mnsbyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ih_mnsbyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-big-right-sharp-fill" /></template>

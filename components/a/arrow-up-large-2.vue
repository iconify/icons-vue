<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmz8e061p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kmz8e061p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:arrow-up-large-2" /></template>

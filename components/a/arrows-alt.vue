<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vyl_93bus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="vyl_93bus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:arrows-alt" /></template>

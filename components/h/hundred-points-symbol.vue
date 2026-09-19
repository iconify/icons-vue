<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ah82h4wex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ah82h4wex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:hundred-points-symbol" /></template>

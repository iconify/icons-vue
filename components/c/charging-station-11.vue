<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-xppwbpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="g-xppwbpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:charging-station-11" /></template>

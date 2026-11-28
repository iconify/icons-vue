<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cy8_od6wc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cy8_od6wc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:file-star" /></template>

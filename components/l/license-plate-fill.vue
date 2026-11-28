<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hgy-j0b3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="hgy-j0b3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:license-plate-fill" /></template>

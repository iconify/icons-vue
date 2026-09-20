<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mrcaziatd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="mrcaziatd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:briefcase-1" /></template>

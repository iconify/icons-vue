<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfm90gbul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sfm90gbul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:flowise-light" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfm-2rsun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sfm-2rsun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:diamond-solid" /></template>

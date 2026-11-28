<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfdi84ohu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rfdi84ohu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:image-refresh" /></template>

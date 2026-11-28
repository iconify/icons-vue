<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/imf8lpb1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="imf8lpb1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:file-image-search" /></template>

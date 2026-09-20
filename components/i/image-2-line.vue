<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rakdz87th.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rakdz87th"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:image-2-line" /></template>

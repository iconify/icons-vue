<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jwcb9nbmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jwcb9nbmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-rotate-counter-clockwise" /></template>

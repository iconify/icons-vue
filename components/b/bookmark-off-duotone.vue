<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y0syes_ml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary y0syes_ml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:bookmark-off-duotone" /></template>

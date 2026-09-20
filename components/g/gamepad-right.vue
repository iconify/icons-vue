<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-cfe4r_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="u-cfe4r_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:gamepad-right" /></template>

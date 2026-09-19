<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/itc5zdbai.css';
import '../../css/o/o6w0dd8_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="itc5zdbai"/><path class="o6w0dd8_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-circle-filled" /></template>

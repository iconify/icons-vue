<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e2c8clb_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e2c8clb_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:inkscape-light" /></template>

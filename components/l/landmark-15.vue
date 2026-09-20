<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vb_7g2bxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="vb_7g2bxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:landmark-15" /></template>

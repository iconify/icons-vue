<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/grf4dx6ip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="grf4dx6ip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:ferry" /></template>

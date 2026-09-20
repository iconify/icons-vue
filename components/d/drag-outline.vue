<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt9lw47qv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="dt9lw47qv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:drag-outline" /></template>

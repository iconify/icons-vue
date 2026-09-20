<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_-9aua6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y_-9aua6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:drag-indicator-duotone" /></template>

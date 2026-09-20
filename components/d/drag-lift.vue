<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oo4arabpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="oo4arabpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:drag-lift" /></template>

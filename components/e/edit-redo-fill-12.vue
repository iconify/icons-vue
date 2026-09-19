<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/umnnux3_u.css';
import '../../css/m/mgoapachr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="umnnux3_u"/><path class="mgoapachr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:edit-redo-fill-12" /></template>

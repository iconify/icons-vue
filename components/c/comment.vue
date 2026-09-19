<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e22g7d7ar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="e22g7d7ar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:comment" /></template>

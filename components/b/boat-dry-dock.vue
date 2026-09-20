<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/refuwn1eq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="refuwn1eq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:boat-dry-dock" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cwv14-5so.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":408};
const content = `<path class="cwv14-5so"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:case-play" /></template>

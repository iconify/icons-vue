<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmfkg_j2b.css';
import '../../css/z/z0r2h759q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="mmfkg_j2b"/><path class="z0r2h759q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:cloud-check" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/csta3d-ey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":445,"height":512};
const content = `<path class="csta3d-ey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:conda" /></template>

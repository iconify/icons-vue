<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sb7ms080d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="sb7ms080d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:file-cabinet" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-kspccne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="d-kspccne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:file-circle-xmark" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gafr-ibcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":434,"height":512};
const content = `<path class="gafr-ibcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:keynote" /></template>

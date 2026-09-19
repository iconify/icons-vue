<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fv37qvdmx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fv37qvdmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:female" /></template>

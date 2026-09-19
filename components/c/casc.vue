<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vxn7l67aj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vxn7l67aj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:casc" /></template>

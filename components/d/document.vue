<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rj8s9obmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rj8s9obmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:document" /></template>

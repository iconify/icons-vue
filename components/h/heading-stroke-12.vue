<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ltq5cfbtl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ltq5cfbtl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:heading-stroke-12" /></template>

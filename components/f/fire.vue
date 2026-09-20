<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dtshw__nt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="dtshw__nt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:fire" /></template>

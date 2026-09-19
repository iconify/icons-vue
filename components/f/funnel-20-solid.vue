<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzb2efb0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="tzb2efb0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:funnel-20-solid" /></template>

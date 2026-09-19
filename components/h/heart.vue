<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vz69oqb2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="vz69oqb2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:heart" /></template>

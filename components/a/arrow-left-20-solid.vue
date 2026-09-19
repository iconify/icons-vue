<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ol-p9lb3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="ol-p9lb3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-left-20-solid" /></template>

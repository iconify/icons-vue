<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trm71o2xf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="trm71o2xf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:docpad" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ekbllctrq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ekbllctrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:arttext" /></template>

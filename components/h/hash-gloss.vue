<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vj3f72bbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vj3f72bbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:hash-gloss" /></template>

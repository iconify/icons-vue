<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sc9g2ibzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sc9g2ibzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:infinity-gloss" /></template>

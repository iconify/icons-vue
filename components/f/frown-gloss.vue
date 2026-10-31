<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oewq_tvoc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oewq_tvoc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:frown-gloss" /></template>

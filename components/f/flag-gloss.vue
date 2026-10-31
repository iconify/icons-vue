<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ug42kdbjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ug42kdbjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:flag-gloss" /></template>

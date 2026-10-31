<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ee8ekuboi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ee8ekuboi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:guitar-gloss" /></template>

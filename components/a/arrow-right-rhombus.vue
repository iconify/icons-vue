<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fsciwwbmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fsciwwbmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-right-rhombus" /></template>

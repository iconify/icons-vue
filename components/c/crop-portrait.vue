<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e2ia8tb4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e2ia8tb4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:crop-portrait" /></template>

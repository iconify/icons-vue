<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v2-n-e3ej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v2-n-e3ej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:link-horizontal-off-duotone-round" /></template>

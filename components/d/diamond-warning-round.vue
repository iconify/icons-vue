<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nmbeninbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nmbeninbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:diamond-warning-round" /></template>

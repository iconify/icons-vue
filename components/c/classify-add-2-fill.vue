<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dhdqm4bif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dhdqm4bif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:classify-add-2-fill" /></template>

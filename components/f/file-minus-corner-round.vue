<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-rlkibmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x-rlkibmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-minus-corner-round" /></template>

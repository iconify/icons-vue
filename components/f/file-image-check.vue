<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o4jq3mbsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o4jq3mbsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:file-image-check" /></template>

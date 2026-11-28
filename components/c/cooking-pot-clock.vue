<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/us7y2n5ix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="us7y2n5ix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:cooking-pot-clock" /></template>

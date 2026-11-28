<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/faebr949z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="faebr949z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:circle-4" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w3i4qabqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w3i4qabqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:banana" /></template>

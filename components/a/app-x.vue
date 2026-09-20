<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8ortrv8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x8ortrv8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:app-x" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/msfe23xvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="msfe23xvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-arrow-left-round" /></template>

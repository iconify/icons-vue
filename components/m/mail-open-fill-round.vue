<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/njcw9_wkp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="njcw9_wkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-open-fill-round" /></template>

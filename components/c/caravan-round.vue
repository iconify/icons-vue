<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g86woor3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g86woor3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:caravan-round" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y4zlm0bkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y4zlm0bkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:car-electric-fill-round" /></template>

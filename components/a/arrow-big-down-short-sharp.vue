<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rmok5rrec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rmok5rrec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-big-down-short-sharp" /></template>

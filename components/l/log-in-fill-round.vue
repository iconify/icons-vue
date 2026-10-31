<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5k00k32a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m5k00k32a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:log-in-fill-round" /></template>

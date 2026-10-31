<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgpg_wbqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rgpg_wbqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:letter-g-duotone-round" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-hp-mnyd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t-hp-mnyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-left-large-duocolor-round" /></template>

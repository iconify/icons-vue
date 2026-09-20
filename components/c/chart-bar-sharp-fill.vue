<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r4m6-cczg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r4m6-cczg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chart-bar-sharp-fill" /></template>

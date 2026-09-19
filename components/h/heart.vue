<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w03xrr2fc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1063,"height":1000};
const content = `<path class="w03xrr2fc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="websymbol:heart" /></template>

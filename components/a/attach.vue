<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h26jykb8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1113,"height":1000};
const content = `<path class="h26jykb8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="websymbol:attach" /></template>

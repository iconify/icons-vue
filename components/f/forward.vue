<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vek2j8b-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1185,"height":1000};
const content = `<path class="vek2j8b-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="websymbol:forward" /></template>

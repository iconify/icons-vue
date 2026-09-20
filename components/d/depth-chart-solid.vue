<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzmz5dn5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="tzmz5dn5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:depth-chart-solid" /></template>

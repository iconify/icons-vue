<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rem1nn86g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rem1nn86g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chart-no-axes-combined-sharp" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7erv32_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u7erv32_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:lungs-sharp" /></template>

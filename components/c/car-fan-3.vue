<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kspyadk-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kspyadk-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:car-fan-3" /></template>

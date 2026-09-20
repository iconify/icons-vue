<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/njc6ft7np.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="njc6ft7np"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:chart-covariate" /></template>

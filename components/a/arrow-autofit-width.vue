<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_cyp9b-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t_cyp9b-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-autofit-width" /></template>

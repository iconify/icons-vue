<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ulhibtbjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ulhibtbjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:logic-not" /></template>

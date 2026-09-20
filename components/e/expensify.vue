<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s36q-6b-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s36q-6b-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:expensify" /></template>

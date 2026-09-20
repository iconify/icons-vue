<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/us8f7bb0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="us8f7bb0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:blazemeter" /></template>

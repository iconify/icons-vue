<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ue1wbd4-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ue1wbd4-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:euro-eur" /></template>

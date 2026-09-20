<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ugn-a1bzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ugn-a1bzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:flip-horizontal-2-line" /></template>

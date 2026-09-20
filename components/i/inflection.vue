<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xl-k__l2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xl-k__l2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:inflection" /></template>

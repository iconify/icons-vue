<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7hp4gblw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l7hp4gblw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chart-pyramid-sharp-fill" /></template>

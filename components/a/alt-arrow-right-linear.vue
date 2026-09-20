<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hh3tv6bzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hh3tv6bzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:alt-arrow-right-linear" /></template>

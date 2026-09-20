<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t8_cwufas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t8_cwufas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:debrid-link" /></template>

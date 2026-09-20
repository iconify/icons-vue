<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eo5d2pbos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eo5d2pbos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:lumen" /></template>

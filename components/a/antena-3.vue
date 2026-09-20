<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gapxmbbgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gapxmbbgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:antena-3" /></template>

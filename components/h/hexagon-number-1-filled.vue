<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ecczycpjj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ecczycpjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:hexagon-number-1-filled" /></template>

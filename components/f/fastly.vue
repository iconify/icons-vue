<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lhh6-acix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lhh6-acix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:fastly" /></template>

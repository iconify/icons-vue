<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nr_nio-1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nr_nio-1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:inkdrop" /></template>

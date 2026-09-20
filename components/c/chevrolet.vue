<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wa4p4804g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wa4p4804g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:chevrolet" /></template>

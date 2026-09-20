<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/chhmsyi2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="chhmsyi2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:adaway" /></template>

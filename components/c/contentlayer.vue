<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/twg23usft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" transform="matrix(.5949 0 0 .61208 9.182 1.311)" class="twg23usft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:contentlayer" /></template>

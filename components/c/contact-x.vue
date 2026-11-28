<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jrr1d9bvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jrr1d9bvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:contact-x" /></template>

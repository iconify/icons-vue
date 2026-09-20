<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nst4jmd1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nst4jmd1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:google-lens" /></template>

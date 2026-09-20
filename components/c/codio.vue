<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/avn5l5gls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="avn5l5gls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:codio" /></template>

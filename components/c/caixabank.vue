<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7a09-mtb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u7a09-mtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:caixabank" /></template>

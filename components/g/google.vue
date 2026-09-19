<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dcy4mgdjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dcy4mgdjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:google" /></template>

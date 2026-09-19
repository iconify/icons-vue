<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-a3n1cad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":961,"height":960};
const content = `<path class="z-a3n1cad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:dominoeight" /></template>

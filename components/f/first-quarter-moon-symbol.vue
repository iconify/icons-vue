<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ftu8mvbwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ftu8mvbwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:first-quarter-moon-symbol" /></template>

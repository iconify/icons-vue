<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7b46bbwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g7b46bbwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:digital-ocean" /></template>

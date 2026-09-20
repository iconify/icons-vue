<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fksw118oz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fksw118oz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:black-candy-light" /></template>

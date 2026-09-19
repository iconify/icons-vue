<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iv-wanbkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iv-wanbkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:caret-forward-circle-sharp" /></template>

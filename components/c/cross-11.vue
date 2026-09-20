<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/roudr1b6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="roudr1b6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:cross-11" /></template>

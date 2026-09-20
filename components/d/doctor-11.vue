<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2zrc-bjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="w2zrc-bjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:doctor-11" /></template>

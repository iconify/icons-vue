<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fhtq3obqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="fhtq3obqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:layers-union-outline" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nbv326bvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="nbv326bvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:airport-terminal" /></template>

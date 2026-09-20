<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nqjs_6btz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="nqjs_6btz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:hexagon-solid" /></template>

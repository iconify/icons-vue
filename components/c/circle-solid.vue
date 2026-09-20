<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-ljiexss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="c-ljiexss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:circle-solid" /></template>

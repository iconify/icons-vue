<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ct4q6eb6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ct4q6eb6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:direction-outline" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z02_g1b5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="z02_g1b5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:black-right-double-triangle" /></template>

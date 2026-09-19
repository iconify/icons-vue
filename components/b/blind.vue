<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ux1cfnjeu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="ux1cfnjeu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:blind" /></template>

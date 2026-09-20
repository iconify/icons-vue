<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxb3bvbeu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="mxb3bvbeu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-arrows-shrink-1-expand-retract-shrink-bigger-big-small-smaller" /></template>

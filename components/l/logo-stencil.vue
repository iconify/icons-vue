<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8ytbtb7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h8ytbtb7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:logo-stencil" /></template>

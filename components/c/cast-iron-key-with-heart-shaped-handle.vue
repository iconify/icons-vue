<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vsvbapugp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="vsvbapugp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:cast-iron-key-with-heart-shaped-handle" /></template>

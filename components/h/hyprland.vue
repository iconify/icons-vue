<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gg6b8sbxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="gg6b8sbxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:hyprland" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/miy_jjbxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":32};
const content = `<path class="miy_jjbxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="et:lightbulb" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3n57acnu.css';
import '../../css/u/ufjhi98xb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="u3n57acnu"/><path class="ufjhi98xb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:folders-20" /></template>

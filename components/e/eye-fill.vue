<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/holrsn7wm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="holrsn7wm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:eye-fill" /></template>

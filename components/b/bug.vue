<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ou0e5zlit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ou0e5zlit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:bug" /></template>

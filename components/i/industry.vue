<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mqat6lbbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="mqat6lbbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:industry" /></template>

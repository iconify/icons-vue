<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h97yosb3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="h97yosb3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:fan-solid" /></template>

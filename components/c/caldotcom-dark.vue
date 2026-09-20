<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vg2xj8bky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":101,"height":22};
const content = `<path class="vg2xj8bky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:caldotcom-dark" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k1fb3obky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k1fb3obky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:deutsche-welle" /></template>

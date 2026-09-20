<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qh5l0m7qc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qh5l0m7qc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:clarifai" /></template>

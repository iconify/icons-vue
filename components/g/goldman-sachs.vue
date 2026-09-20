<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uy-ckacit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uy-ckacit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:goldman-sachs" /></template>

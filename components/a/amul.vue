<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/du2t3dkjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="du2t3dkjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:amul" /></template>

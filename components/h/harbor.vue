<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z1xlcq7az.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z1xlcq7az"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:harbor" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/surbmpbbd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="surbmpbbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:chromatic" /></template>

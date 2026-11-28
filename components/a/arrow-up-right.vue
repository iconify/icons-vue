<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mo583e5rz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mo583e5rz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:arrow-up-right" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nv9x1_l0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nv9x1_l0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:folders-lock" /></template>

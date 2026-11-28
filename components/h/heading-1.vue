<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p771xi_ye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p771xi_ye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:heading-1" /></template>

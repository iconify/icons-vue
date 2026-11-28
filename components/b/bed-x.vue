<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mjb0yu-2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mjb0yu-2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:bed-x" /></template>

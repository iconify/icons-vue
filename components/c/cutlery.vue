<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uu0-ifbnz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uu0-ifbnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:cutlery" /></template>

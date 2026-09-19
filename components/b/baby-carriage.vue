<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iik2gdc7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iik2gdc7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:baby-carriage" /></template>

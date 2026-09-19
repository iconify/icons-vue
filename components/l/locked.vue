<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sloln0bvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":24};
const content = `<path class="sloln0bvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:locked" /></template>

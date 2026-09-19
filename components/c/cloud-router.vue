<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ij_x4y6-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ij_x4y6-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:cloud-router" /></template>

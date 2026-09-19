<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ry8pu_a8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ry8pu_a8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:algolia" /></template>

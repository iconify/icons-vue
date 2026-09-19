<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mvys67bog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":24};
const content = `<path class="mvys67bog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:jenkins" /></template>

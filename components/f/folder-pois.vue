<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p9b_kub7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="p9b_kub7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:folder-pois" /></template>

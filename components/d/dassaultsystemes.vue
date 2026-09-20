<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ruv4d3bww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ruv4d3bww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:dassaultsystemes" /></template>

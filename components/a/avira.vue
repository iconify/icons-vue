<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yr-sl2bzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yr-sl2bzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:avira" /></template>

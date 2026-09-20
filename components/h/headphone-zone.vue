<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-8xtcnba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m-8xtcnba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:headphone-zone" /></template>

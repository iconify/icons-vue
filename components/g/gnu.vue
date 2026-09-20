<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fbgo2sbuo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fbgo2sbuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:gnu" /></template>

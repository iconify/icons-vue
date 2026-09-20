<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aza816-6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aza816-6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:avast" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z21m6mbuy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z21m6mbuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:google-translate" /></template>

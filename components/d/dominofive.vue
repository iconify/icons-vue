<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fo-ux8bhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":961,"height":960};
const content = `<path class="fo-ux8bhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:dominofive" /></template>

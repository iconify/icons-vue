<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ppmx33bax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":66.61,"height":34.03,"left":249.8,"top":192.24};
const content = `<path class="ppmx33bax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:best-western" /></template>

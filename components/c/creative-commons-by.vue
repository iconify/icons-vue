<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gol34_mdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="gol34_mdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:creative-commons-by" /></template>

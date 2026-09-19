<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iruil4alm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="iruil4alm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:ioxhost" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mqraa8bjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="mqraa8bjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:film" /></template>

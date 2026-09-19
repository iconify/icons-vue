<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_bbn7bzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="f_bbn7bzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:innosoft" /></template>

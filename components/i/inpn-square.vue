<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6thpwbnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="y6thpwbnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:inpn-square" /></template>

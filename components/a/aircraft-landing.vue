<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_5_sylip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w_5_sylip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:aircraft-landing" /></template>

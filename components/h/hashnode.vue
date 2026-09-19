<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdp2_hgrm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="mdp2_hgrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:hashnode" /></template>

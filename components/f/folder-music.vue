<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_plpbbah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="u_plpbbah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:folder-music" /></template>

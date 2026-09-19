<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nd78m2pfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="nd78m2pfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:arpup" /></template>

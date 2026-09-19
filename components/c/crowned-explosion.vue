<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ycc1cgbca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ycc1cgbca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:crowned-explosion" /></template>

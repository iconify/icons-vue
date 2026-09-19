<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4hmrzunf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f4hmrzunf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:battery-pack-alt" /></template>

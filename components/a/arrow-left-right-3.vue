<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swa1uqbat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="swa1uqbat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:arrow-left-right-3" /></template>

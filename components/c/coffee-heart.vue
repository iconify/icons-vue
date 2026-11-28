<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmg5gpb5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gmg5gpb5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:coffee-heart" /></template>

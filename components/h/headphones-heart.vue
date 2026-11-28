<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wtt60bhpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wtt60bhpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:headphones-heart" /></template>

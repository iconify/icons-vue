<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pepqk8x2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pepqk8x2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:ice-cream-heart" /></template>

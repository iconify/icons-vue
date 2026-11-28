<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gb3iyoc2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gb3iyoc2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:ice-cream-heart" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rw1drz2ie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rw1drz2ie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:fish-heart" /></template>

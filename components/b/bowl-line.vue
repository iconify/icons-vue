<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/od5dngbta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="od5dngbta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:bowl-line" /></template>

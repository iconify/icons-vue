<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwa9ygbuw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fwa9ygbuw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:beach-bag-big" /></template>

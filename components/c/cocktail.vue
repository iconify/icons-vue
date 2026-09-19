<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rh-3_uvfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rh-3_uvfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:cocktail" /></template>

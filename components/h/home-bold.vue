<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gllq9sb3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gllq9sb3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:home-bold" /></template>

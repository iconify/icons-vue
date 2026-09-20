<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ps1-t3blf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ps1-t3blf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:foodpanda" /></template>

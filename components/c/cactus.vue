<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jlcua3j-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jlcua3j-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:cactus" /></template>

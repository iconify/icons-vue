<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h0sizfbbg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="h0sizfbbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:bacon" /></template>

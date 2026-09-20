<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ud97l4bva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="ud97l4bva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:artist-song" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/batsi3o4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="batsi3o4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:align-back-1-solid" /></template>

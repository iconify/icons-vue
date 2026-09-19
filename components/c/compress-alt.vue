<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nza448bsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="nza448bsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:compress-alt" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ps_32bbnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="ps_32bbnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:fill-drip" /></template>

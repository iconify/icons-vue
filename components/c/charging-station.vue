<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n6ku53bvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="n6ku53bvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:charging-station" /></template>

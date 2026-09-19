<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pu8eqhbvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="pu8eqhbvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:heart-circle-bolt" /></template>

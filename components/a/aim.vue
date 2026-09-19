<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bz4gnyzmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":569,"height":694};
const content = `<path class="bz4gnyzmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:aim" /></template>

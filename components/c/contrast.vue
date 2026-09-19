<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y8j1_70vb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y8j1_70vb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:contrast" /></template>

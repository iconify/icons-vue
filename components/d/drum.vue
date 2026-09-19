<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wrx5y-pzi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wrx5y-pzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:drum" /></template>

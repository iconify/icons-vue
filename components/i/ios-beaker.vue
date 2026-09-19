<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h14ltnbwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h14ltnbwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-beaker" /></template>

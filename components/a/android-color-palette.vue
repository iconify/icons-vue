<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5vxb6zvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q5vxb6zvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:android-color-palette" /></template>

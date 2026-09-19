<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cr0vp1bbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cr0vp1bbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:android-arrow-dropup" /></template>

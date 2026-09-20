<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h1gzu-buu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h1gzu-buu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dub" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lfy8vzb3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lfy8vzb3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:firebase-dark" /></template>

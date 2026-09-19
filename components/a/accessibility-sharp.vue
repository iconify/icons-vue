<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3j-vtbmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u3j-vtbmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:accessibility-sharp" /></template>

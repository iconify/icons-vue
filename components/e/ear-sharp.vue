<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k98tvglog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k98tvglog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ear-sharp" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uy0lpbywg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uy0lpbywg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:calmness-dark" /></template>

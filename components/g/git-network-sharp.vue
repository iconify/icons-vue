<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-f9gnybm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w-f9gnybm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:git-network-sharp" /></template>

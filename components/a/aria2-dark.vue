<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9ztp1byc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z9ztp1byc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:aria2-dark" /></template>

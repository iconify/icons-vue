<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/be58yvdwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="be58yvdwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:audiosilo-light" /></template>

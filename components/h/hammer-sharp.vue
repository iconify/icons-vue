<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxnw_pr2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xxnw_pr2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:hammer-sharp" /></template>

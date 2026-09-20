<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lj5le3ddq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lj5le3ddq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:iventoy-light" /></template>

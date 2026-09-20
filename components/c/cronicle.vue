<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vk3q6nbal.css';
import '../../css/z/z1mt3ubli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vk3q6nbal"/><path class="z1mt3ubli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cronicle" /></template>

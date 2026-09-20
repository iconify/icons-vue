<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kz5t110yc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kz5t110yc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:corecontrol-dark" /></template>

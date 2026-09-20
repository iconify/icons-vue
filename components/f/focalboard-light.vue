<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxj88veqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xxj88veqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:focalboard-light" /></template>

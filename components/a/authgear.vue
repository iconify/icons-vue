<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z2_j2sbxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z2_j2sbxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:authgear" /></template>

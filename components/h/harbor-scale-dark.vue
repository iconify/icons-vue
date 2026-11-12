<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ooo7ryxbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ooo7ryxbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:harbor-scale-dark" /></template>

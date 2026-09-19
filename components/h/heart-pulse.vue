<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvtwuab4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dvtwuab4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:heart-pulse" /></template>

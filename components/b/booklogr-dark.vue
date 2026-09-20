<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_g9pwbmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p_g9pwbmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:booklogr-dark" /></template>

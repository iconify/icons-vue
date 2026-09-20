<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fg3759byh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fg3759byh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:amurex-dark" /></template>

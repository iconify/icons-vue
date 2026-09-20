<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hurrjdb5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hurrjdb5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:flowise-dark" /></template>

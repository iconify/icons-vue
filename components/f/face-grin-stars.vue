<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipfdw6b6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ipfdw6b6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:face-grin-stars" /></template>

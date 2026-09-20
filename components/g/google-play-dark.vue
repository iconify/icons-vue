<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fbcelkbyy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fbcelkbyy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:google-play-dark" /></template>

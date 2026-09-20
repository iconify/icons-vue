<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hsw6ydedy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hsw6ydedy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:laudspeaker-dark" /></template>

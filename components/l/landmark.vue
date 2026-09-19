<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r4aqdmb7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r4aqdmb7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:landmark" /></template>

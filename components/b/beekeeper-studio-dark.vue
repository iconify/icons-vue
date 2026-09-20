<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/umr1o5bgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="umr1o5bgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:beekeeper-studio-dark" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_xp4vbpg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y_xp4vbpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:codepen-light" /></template>

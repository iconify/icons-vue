<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zamm8q_ux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zamm8q_ux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:anibridge-dark" /></template>

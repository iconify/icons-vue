<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/agc9_jb8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="agc9_jb8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:frigate-dark" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1d41h4vt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f1d41h4vt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:doppler-light" /></template>

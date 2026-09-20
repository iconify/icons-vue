<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ie5ghf9ci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ie5ghf9ci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:anonymousoverflow-dark" /></template>
